<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjn7jibdx.css';
import '../../css/x/xd_e_q94j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kjn7jibdx"/><path class="xd_e_q94j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:article-add" {...props}></Icon>
