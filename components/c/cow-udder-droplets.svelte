<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf73r1lpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sf73r1lpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:cow-udder-droplets" {...props}></Icon>
