<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysrry-bqw.css';
import '../../css/j/jbyiw1r0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysrry-bqw"/><path class="jbyiw1r0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-down-left-circle-filled" {...props}></Icon>
