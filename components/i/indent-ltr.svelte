<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcej5bcxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fcej5bcxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:indent-ltr" {...props}></Icon>
