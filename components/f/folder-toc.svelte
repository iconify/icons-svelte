<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru_ztdbjh.css';
import '../../css/h/hhxngibkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ru_ztdbjh"/><path class="hhxngibkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-toc" {...props}></Icon>
