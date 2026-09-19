<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbiwg9rpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pbiwg9rpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:hammer" {...props}></Icon>
