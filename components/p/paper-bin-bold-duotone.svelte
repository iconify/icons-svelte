<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-wzpbwcp.css';
import '../../css/c/cgsdd0bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-wzpbwcp"/><path clip-rule="evenodd" class="cgsdd0bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paper-bin-bold-duotone" {...props}></Icon>
