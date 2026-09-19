<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjzmy7b4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yjzmy7b4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:confluence" {...props}></Icon>
