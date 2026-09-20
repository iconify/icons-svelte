<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd_qk7bir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd_qk7bir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:low-beam" {...props}></Icon>
