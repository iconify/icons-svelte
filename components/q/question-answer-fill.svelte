<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hefpc1big.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hefpc1big"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:question-answer-fill" {...props}></Icon>
