<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hek2idb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hek2idb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:align-right" {...props}></Icon>
