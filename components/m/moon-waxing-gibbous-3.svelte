<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih0mf8ell.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="ih0mf8ell"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-waxing-gibbous-3" {...props}></Icon>
