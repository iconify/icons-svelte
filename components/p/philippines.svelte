<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xomdi8b2s.css';
import '../../css/n/nuemgvbfx.css';
import '../../css/c/cc6_nwbfm.css';
import '../../css/d/db4425i8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="xomdi8b2s"/><path class="nuemgvbfx"/><path class="cc6_nwbfm"/><path class="db4425i8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:philippines" {...props}></Icon>
