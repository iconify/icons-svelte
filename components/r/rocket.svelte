<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg2rmmb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hg2rmmb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:rocket" {...props}></Icon>
