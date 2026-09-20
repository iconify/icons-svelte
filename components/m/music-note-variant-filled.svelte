<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbivq1bzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbivq1bzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-note-variant-filled" {...props}></Icon>
