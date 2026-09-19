<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3_frb7dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="k3_frb7dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:grin-beam-sweat" {...props}></Icon>
