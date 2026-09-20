<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg6xadbuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="qg6xadbuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:graph-bar-increase" {...props}></Icon>
