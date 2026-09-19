<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc3srnbcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cc3srnbcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:center-stroke-16" {...props}></Icon>
