<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhdqeq3jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fhdqeq3jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:list-numbered-rtl" {...props}></Icon>
