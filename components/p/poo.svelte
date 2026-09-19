<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zqmu46v8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zqmu46v8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:poo" {...props}></Icon>
