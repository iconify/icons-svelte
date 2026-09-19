<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6hhcjbid.css';
import '../../css/r/ryyiu8v4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="w6hhcjbid"/><path class="ryyiu8v4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:frame" {...props}></Icon>
