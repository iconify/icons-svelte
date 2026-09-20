<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn0n5kbor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cn0n5kbor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:disconnected-circle-filled" {...props}></Icon>
