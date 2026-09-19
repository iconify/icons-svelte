<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdk9atbuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":472};
const content = `<path class="fdk9atbuo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:phone" {...props}></Icon>
