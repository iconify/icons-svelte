<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_5by1bgh.css';
import '../../css/h/hckr-tb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="b_5by1bgh"/><path class="hckr-tb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pinterest" {...props}></Icon>
