<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eie2zmxnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="eie2zmxnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:money-check" {...props}></Icon>
