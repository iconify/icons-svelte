<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u65hmsmhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1536};
const content = `<path class="u65hmsmhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:fast-backward" {...props}></Icon>
