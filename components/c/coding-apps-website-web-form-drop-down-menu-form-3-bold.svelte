<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw3_kmb9z.css';
import '../../css/r/r9zynwktx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vw3_kmb9z"/><path class="r9zynwktx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-web-form-drop-down-menu-form-3-bold" {...props}></Icon>
