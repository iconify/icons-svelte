<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_298ebcy.css';
import '../../css/q/qou13c05m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d_298ebcy"/><path class="qou13c05m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:battery-full-filled" {...props}></Icon>
