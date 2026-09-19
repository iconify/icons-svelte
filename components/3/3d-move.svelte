<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3s2gdcyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3s2gdcyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:3d-move" {...props}></Icon>
