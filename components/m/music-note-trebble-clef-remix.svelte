<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmjjd_bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="vmjjd_bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:music-note-trebble-clef-remix" {...props}></Icon>
