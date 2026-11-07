<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/b/b4m30hhex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="b4m30hhex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:euro-bold-duotone" {...props}></Icon>
