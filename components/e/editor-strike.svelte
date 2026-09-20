<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbheybcls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hbheybcls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-strike" {...props}></Icon>
