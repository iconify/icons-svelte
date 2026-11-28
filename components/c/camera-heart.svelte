<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/agw2k9bgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agw2k9bgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:camera-heart" {...props}></Icon>
