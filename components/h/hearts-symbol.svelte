<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz2eh4s9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kz2eh4s9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hearts-symbol" {...props}></Icon>
