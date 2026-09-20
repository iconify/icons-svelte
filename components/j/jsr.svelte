<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb-q3w5sr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fb-q3w5sr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:jsr" {...props}></Icon>
