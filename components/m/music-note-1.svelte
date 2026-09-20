<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj0an3bgo.css';
import '../../css/m/mjrq3v7lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj0an3bgo"/><path class="mjrq3v7lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:music-note-1" {...props}></Icon>
