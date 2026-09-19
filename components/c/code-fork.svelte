<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqq_5joia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zqq_5joia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:code-fork" {...props}></Icon>
