<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj_6xpl-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xj_6xpl-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:creative-commons-share" {...props}></Icon>
