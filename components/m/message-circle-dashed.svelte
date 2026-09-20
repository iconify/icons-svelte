<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-n4_vbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-n4_vbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-circle-dashed" {...props}></Icon>
