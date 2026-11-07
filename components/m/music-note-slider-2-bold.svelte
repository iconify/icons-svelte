<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugxjo2rua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugxjo2rua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-slider-2-bold" {...props}></Icon>
