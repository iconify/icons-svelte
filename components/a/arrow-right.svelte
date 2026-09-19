<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6vg5ubaa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l6vg5ubaa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-right" {...props}></Icon>
