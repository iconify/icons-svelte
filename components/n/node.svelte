<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak85jub6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ak85jub6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:node" {...props}></Icon>
