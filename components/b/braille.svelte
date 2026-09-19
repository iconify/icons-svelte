<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1oyp3b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="f1oyp3b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:braille" {...props}></Icon>
