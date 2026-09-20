<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/niy991b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="niy991b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:movie-ai-filled" {...props}></Icon>
