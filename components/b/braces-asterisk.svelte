<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f10s-hb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="f10s-hb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:braces-asterisk" {...props}></Icon>
