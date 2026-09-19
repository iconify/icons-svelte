<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sffbs1avt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sffbs1avt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:east-wind-mahjong" {...props}></Icon>
