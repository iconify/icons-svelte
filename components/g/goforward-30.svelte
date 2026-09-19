<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0p73jorn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i0p73jorn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:goforward-30" {...props}></Icon>
