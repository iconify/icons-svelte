<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/au_v0wb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="au_v0wb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cigarette-with-smoke-curl" {...props}></Icon>
