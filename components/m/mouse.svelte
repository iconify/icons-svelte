<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qna1oz1fb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qna1oz1fb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:mouse" {...props}></Icon>
