<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p23qu-5zj.css';
import '../../css/f/fg-2q4b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p23qu-5zj"/><path class="fg-2q4b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:go-mod" {...props}></Icon>
