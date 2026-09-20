<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kihstx6sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kihstx6sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:exclamation-point-beside-question-mark" {...props}></Icon>
