<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1t0vjbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f1t0vjbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-4-outline" {...props}></Icon>
