<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7saf9b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="y7saf9b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-blank-stroke-12" {...props}></Icon>
