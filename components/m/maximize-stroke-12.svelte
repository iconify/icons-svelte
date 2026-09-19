<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl4ijetfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="nl4ijetfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:maximize-stroke-12" {...props}></Icon>
