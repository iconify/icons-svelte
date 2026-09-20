<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4d1tub4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e4d1tub4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:double-chevron-end-ltr" {...props}></Icon>
