<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt5aatsrh.css';
import '../../css/x/xsgq8ckwo.css';
import '../../css/f/fodrk9f3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kt5aatsrh"/><path class="xsgq8ckwo"/><path class="fodrk9f3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:music-note-circle-block-1" {...props}></Icon>
