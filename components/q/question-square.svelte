<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfd1qnxoq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="rfd1qnxoq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:question-square" {...props}></Icon>
