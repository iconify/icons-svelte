<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/q/qruq-3brg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path clip-rule="evenodd" class="qruq-3brg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:circle-bottom-down-bold-duotone" {...props}></Icon>
