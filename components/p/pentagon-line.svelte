<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp4kg59fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sp4kg59fy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pentagon-line" {...props}></Icon>
