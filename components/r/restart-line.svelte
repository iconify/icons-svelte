<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9_ow_xmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9_ow_xmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:restart-line" {...props}></Icon>
