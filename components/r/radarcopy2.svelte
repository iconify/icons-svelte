<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9y04fb7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="f9y04fb7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:radarcopy2" {...props}></Icon>
