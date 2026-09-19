<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzhd2pbal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fzhd2pbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:one-of-bamboos-mahjong-ss02" {...props}></Icon>
