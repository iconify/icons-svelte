<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_dvk81hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z_dvk81hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-3-fill" {...props}></Icon>
