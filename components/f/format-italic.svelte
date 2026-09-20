<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/defsf5bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="defsf5bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:format-italic" {...props}></Icon>
