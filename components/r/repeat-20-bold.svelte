<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmh3e9bdx.css';
import '../../css/z/z_yq7-buc.css';
import '../../css/y/yg_0l029v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wmh3e9bdx"/><path class="z_yq7-buc"/><path class="yg_0l029v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:repeat-20-bold" {...props}></Icon>
