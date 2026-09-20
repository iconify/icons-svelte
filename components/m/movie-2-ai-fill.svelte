<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m68bhtbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m68bhtbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:movie-2-ai-fill" {...props}></Icon>
