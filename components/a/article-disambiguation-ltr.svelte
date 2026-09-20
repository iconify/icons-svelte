<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlzgxp-_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nlzgxp-_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-disambiguation-ltr" {...props}></Icon>
