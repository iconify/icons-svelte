<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upaw9jfrj.css';
import '../../css/p/p56h_bbeb.css';
import '../../css/v/vece7s5mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upaw9jfrj"/><path class="p56h_bbeb"/><path class="vece7s5mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:message-question-mark" {...props}></Icon>
