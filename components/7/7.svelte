<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uctknnc3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="uctknnc3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:7" {...props}></Icon>
