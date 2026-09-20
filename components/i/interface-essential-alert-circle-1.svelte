<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwz563b2r.css';
import '../../css/e/e_3s_pztg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cwz563b2r"/><path class="e_3s_pztg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-alert-circle-1" {...props}></Icon>
