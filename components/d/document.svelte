<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv6nmjb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cv6nmjb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:document" {...props}></Icon>
