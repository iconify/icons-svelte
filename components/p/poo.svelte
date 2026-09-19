<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vugygd5du.css';
import '../../css/b/bjggiqboe.css';
import '../../css/f/faeazbblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vugygd5du"/><path class="bjggiqboe"/><path class="faeazbblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:poo" {...props}></Icon>
