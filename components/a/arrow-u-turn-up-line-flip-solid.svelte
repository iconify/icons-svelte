<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ftjmqqbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ftjmqqbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-u-turn-up-line-flip-solid" {...props}></Icon>
