<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzzz3ybdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="qzzz3ybdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:gobackward" {...props}></Icon>
