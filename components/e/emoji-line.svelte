<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0bwvu1em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0bwvu1em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:emoji-line" {...props}></Icon>
