<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp2y35std.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp2y35std"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microphone-alt-2-filled" {...props}></Icon>
