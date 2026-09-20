<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap8ygib1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ap8ygib1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:minus" {...props}></Icon>
