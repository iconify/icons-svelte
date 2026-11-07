<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-4tj5bwa.css';
import '../../css/x/x7-wb_rwz.css';
import '../../css/c/ctjzn5myy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-4tj5bwa"/><path class="x7-wb_rwz"/><path class="ctjzn5myy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-3-bold-duotone" {...props}></Icon>
