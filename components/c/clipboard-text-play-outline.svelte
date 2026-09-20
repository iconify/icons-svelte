<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z601x6bil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z601x6bil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-text-play-outline" {...props}></Icon>
