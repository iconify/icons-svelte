<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxoyzrbdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxoyzrbdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:alarm-warning-line" {...props}></Icon>
