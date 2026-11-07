<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcsc5yb1p.css';
import '../../css/y/yftbzgjri.css';
import '../../css/e/elfm62bxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcsc5yb1p"/><path class="yftbzgjri"/><path clip-rule="evenodd" class="elfm62bxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:palette-round-bold" {...props}></Icon>
