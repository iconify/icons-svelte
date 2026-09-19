<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe_qtl4kr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fe_qtl4kr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:inbox-fill-16" {...props}></Icon>
