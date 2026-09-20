<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_b0erywf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="s_b0erywf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:lift-gate-10" {...props}></Icon>
