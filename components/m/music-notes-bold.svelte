<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny2z_jjno.css';
import '../../css/m/m33dd1b0b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ny2z_jjno"/><path class="m33dd1b0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-notes-bold" {...props}></Icon>
