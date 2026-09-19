<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1365bb5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q1365bb5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:canadian-maple-leaf" {...props}></Icon>
