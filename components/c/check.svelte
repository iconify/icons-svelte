<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxosiwbpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":376,"height":384};
const content = `<path class="rxosiwbpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:check" {...props}></Icon>
