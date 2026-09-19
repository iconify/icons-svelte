<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys838abcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="ys838abcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:openedition" {...props}></Icon>
