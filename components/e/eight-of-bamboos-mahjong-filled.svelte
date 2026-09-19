<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmvb7mbre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="mmvb7mbre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:eight-of-bamboos-mahjong-filled" {...props}></Icon>
