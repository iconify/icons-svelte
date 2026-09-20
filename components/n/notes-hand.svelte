<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md8en7cla.css';
import '../../css/p/p1hqjib3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="md8en7cla"/><path class="p1hqjib3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:notes-hand" {...props}></Icon>
