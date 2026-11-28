<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6yti7l8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6yti7l8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-left" {...props}></Icon>
