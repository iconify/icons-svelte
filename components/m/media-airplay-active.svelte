<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vzio_6m8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vzio_6m8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-airplay-active" {...props}></Icon>
