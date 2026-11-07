<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/svsjy1b4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="svsjy1b4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-in-eaved-leanto-shelter" {...props}></Icon>
