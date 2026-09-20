<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zci6vmbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zci6vmbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-position-bottom-right" {...props}></Icon>
