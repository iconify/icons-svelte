<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgy6b1-ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zgy6b1-ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:firefox-browser" {...props}></Icon>
