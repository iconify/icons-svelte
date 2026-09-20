<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esa6e0o2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="esa6e0o2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:computer-logo-windows-2-os-system-microsoft" {...props}></Icon>
