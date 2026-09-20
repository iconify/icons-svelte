<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx7e35btp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="sx7e35btp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:night-cloudy-windy" {...props}></Icon>
