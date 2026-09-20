<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6r127bgj.css';
import '../../css/z/zta7gebwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q6r127bgj"/><path class="zta7gebwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:messages-bubble-square-text" {...props}></Icon>
