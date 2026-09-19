<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyfwd4byf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyfwd4byf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:globe-alt-3-filled" {...props}></Icon>
