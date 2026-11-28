<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njcx8jb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="njcx8jb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:crosshair" {...props}></Icon>
