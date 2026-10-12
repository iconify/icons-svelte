<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwg583h1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bwg583h1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:emoji-upset-fill-20" {...props}></Icon>
