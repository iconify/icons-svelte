<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpm6ldb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kpm6ldb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:eight-of-circles-mahjong" {...props}></Icon>
