<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asu8thb_w.css';
import '../../css/y/yzgrvsbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="asu8thb_w"/><path class="yzgrvsbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:hand" {...props}></Icon>
