<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_y2kibug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="r_y2kibug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="doodle-icons:ellipsis" {...props}></Icon>
