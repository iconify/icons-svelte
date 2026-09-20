<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmd_ombao.css';
import '../../css/e/ejoji3b3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmd_ombao"/><path class="ejoji3b3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:hospital-filled" {...props}></Icon>
