<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpz2yhb6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bpz2yhb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:photo-sensor-2" {...props}></Icon>
