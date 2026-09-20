<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-wk-pbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o-wk-pbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-distribute-horizontal" {...props}></Icon>
