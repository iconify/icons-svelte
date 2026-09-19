<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev36-ybhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ev36-ybhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:codiepie" {...props}></Icon>
