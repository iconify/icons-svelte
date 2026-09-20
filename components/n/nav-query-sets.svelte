<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh_buwbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hh_buwbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-query-sets" {...props}></Icon>
