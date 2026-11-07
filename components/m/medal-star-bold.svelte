<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yccjtab6a.css';
import '../../css/c/ctt96pn4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yccjtab6a"/><path class="ctt96pn4i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-bold" {...props}></Icon>
