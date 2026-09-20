<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru_ztdbjh.css';
import '../../css/p/pnudnz5ri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ru_ztdbjh"/><path class="pnudnz5ri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-windows" {...props}></Icon>
