<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jseswachs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jseswachs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:italic-gloss" {...props}></Icon>
