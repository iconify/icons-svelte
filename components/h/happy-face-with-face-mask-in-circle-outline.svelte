<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfolds2ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xfolds2ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:happy-face-with-face-mask-in-circle-outline" {...props}></Icon>
