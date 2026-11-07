<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je1sviibk.css';
import '../../css/l/lj99_bbii.css';
import '../../css/e/e4t4l5b9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="je1sviibk"/><path class="lj99_bbii"/><path class="e4t4l5b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bedside-table-3-bold-duotone" {...props}></Icon>
