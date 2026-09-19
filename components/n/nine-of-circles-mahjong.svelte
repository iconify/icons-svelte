<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6wi8bbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="o6wi8bbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:nine-of-circles-mahjong" {...props}></Icon>
