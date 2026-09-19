<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx2hbdw_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="fx2hbdw_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:6-square" {...props}></Icon>
