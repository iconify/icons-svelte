<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b630ko33l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b630ko33l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:airplane-mode-16" {...props}></Icon>
