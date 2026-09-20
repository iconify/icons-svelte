<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz34tx__k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zz34tx__k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:angular" {...props}></Icon>
