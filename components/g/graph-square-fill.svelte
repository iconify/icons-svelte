<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw__72b_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="fw__72b_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:graph-square-fill" {...props}></Icon>
