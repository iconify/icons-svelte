<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1fp4ibvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":504,"height":512};
const content = `<path class="v1fp4ibvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:grin-beam-sweat" {...props}></Icon>
