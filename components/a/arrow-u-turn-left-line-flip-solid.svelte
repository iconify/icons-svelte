<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvbrrab-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvbrrab-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-left-line-flip-solid" {...props}></Icon>
