<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rj_6wwzvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rj_6wwzvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:figma-flatten-selection" {...props}></Icon>
