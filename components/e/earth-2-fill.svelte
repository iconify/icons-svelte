<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/heco3vfik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="heco3vfik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:earth-2-fill" {...props}></Icon>
