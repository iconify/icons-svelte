<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ef25pac2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ef25pac2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:playlist-heart" {...props}></Icon>
