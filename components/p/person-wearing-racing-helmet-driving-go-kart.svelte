<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8pyggqfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f8pyggqfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-wearing-racing-helmet-driving-go-kart" {...props}></Icon>
