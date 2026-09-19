<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy60grbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oy60grbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-file-storage" {...props}></Icon>
