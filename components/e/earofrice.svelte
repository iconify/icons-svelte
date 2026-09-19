<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly_b0dbrd.css';
import '../../css/j/joidnyzty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ly_b0dbrd"/><path class="joidnyzty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:earofrice" {...props}></Icon>
