<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x16refvya.css';
import '../../css/a/a9mph4b6u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x16refvya"/><path class="a9mph4b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-rtl" {...props}></Icon>
