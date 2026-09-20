<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qudpbqb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qudpbqb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:roman-numeral-i-above-water" {...props}></Icon>
