<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxmzmm0yv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="cxmzmm0yv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:back-mahjong-filled" {...props}></Icon>
