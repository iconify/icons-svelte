<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjzxlob2s.css';
import '../../css/f/fb-q3w5sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sjzxlob2s"/><path class="fb-q3w5sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:jsr-light" {...props}></Icon>
