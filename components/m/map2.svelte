<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg6-sxb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg6-sxb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:map2" {...props}></Icon>
