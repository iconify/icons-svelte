<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uiwvyc24j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uiwvyc24j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:music-note-solid" {...props}></Icon>
