<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij_t_sbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ij_t_sbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:caret-left" {...props}></Icon>
