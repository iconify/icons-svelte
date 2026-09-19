<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqhd8xb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="zqhd8xb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:open-with" {...props}></Icon>
