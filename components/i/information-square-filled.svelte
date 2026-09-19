<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpmw0obfn.css';
import '../../css/x/x83nu3j7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jpmw0obfn"/><path class="x83nu3j7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:information-square-filled" {...props}></Icon>
