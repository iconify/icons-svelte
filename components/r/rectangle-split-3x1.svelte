<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im61p5bjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="im61p5bjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:rectangle-split-3x1" {...props}></Icon>
