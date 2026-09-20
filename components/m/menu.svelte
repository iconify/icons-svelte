<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/haa_wlj3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="haa_wlj3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:menu" {...props}></Icon>
