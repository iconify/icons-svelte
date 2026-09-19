<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbmekrbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbmekrbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:aquarium" {...props}></Icon>
