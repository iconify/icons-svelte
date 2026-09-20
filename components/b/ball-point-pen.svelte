<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hg403wb_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="hg403wb_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:ball-point-pen" {...props}></Icon>
