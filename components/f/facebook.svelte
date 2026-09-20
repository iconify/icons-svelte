<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx9ipob0c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yx9ipob0c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:facebook" {...props}></Icon>
