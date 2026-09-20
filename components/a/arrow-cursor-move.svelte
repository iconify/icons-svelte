<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8a631bpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="q8a631bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:arrow-cursor-move" {...props}></Icon>
