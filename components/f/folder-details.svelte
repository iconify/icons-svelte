<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wotujmrpr.css';
import '../../css/s/sm_hxib8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wotujmrpr"/><path class="sm_hxib8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:folder-details" {...props}></Icon>
