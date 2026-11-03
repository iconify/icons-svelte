<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_5by1bgh.css';
import '../../css/f/fuuchc-tk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="b_5by1bgh"/><path class="fuuchc-tk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:pinterest" {...props}></Icon>
