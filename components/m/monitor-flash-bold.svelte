<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufjmd4l2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufjmd4l2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:monitor-flash-bold" {...props}></Icon>
