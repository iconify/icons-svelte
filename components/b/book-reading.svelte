<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p07bz681w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="p07bz681w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:book-reading" {...props}></Icon>
