<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a24-d1bxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="a24-d1bxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:emoji-grin-fill-20" {...props}></Icon>
