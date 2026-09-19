<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvr_rccxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="yvr_rccxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-regular:caret-square-left" {...props}></Icon>
