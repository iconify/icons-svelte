<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp6kl1uty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wp6kl1uty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plus-outline" {...props}></Icon>
