<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxkx06lzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="hxkx06lzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:dizzy" {...props}></Icon>
