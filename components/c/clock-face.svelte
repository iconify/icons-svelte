<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdtm8jb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qdtm8jb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:clock-face" {...props}></Icon>
