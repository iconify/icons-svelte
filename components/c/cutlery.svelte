<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zads2pb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zads2pb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:cutlery" {...props}></Icon>
