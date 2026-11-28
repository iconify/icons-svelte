<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew7pgvbcs.css';
import '../../css/i/i6yti7l8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ew7pgvbcs secondary"/><path class="i6yti7l8q primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-big-left-duo" {...props}></Icon>
