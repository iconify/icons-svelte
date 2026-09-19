<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_3v7z53s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="i_3v7z53s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:medkit" {...props}></Icon>
