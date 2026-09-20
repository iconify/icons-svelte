<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjxclds3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sjxclds3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-check" {...props}></Icon>
