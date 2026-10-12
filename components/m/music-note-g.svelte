<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hblsujbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hblsujbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:music-note-g" {...props}></Icon>
