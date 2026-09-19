<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zf-z8obrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zf-z8obrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:joker-mahjong" {...props}></Icon>
