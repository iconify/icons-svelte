<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtge1ybso.css';
import '../../css/u/ujy_e8uzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vtge1ybso"/><path class="ujy_e8uzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-like" {...props}></Icon>
