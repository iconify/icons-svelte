<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys6vs2qzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys6vs2qzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-1-line" {...props}></Icon>
