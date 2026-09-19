<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hblk6ibbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hblk6ibbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:audr" {...props}></Icon>
