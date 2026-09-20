<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6j7t_y7g.css';
import '../../css/o/od4citb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6j7t_y7g"/><path class="od4citb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:playlist-download-bold" {...props}></Icon>
