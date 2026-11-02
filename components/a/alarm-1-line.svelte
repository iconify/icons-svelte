<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxbi9rt5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxbi9rt5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alarm-1-line" {...props}></Icon>
