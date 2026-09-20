<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erp53acgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="erp53acgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-redirect-ltr" {...props}></Icon>
