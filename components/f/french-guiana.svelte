<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6ysyvb8h.css';
import '../../css/w/wjt581t1z.css';
import '../../css/q/qfcqjabfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="r6ysyvb8h"/><path class="wjt581t1z"/><path class="qfcqjabfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:french-guiana" {...props}></Icon>
