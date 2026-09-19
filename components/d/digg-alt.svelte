<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hubdunbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":464};
const content = `<path class="hubdunbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:digg-alt" {...props}></Icon>
