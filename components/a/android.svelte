<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2met5b4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h2met5b4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:android" {...props}></Icon>
