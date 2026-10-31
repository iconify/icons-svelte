<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzfrzlhey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fzfrzlhey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bus-fill-round" {...props}></Icon>
