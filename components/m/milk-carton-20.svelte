<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht5i-fb7m.css';
import '../../css/p/pa8jkb1da.css';
import '../../css/c/cfktgscfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ht5i-fb7m"/><path class="pa8jkb1da"/><path class="cfktgscfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:milk-carton-20" {...props}></Icon>
