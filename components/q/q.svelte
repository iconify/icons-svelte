<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xna4wac8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":382,"height":512};
const content = `<path class="xna4wac8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:q" {...props}></Icon>
