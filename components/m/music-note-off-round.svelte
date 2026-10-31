<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqq9qe5dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqq9qe5dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-note-off-round" {...props}></Icon>
