<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9jpwwt3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9jpwwt3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cards-playing-spade" {...props}></Icon>
