<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbvbhob8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="xbvbhob8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gobackward-30" {...props}></Icon>
