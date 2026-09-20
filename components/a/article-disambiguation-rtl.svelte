<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/batb0rb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="batb0rb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-disambiguation-rtl" {...props}></Icon>
