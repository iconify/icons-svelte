<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j55fwyb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1408};
const content = `<path class="j55fwyb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:newspaper-o" {...props}></Icon>
