<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw9ndx6fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw9ndx6fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cigarette-off-fill" {...props}></Icon>
