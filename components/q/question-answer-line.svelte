<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9d8fjder.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w9d8fjder"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:question-answer-line" {...props}></Icon>
