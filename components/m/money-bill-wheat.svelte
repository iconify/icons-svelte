<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aybxl6yxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="aybxl6yxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:money-bill-wheat" {...props}></Icon>
