<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of1h860am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="of1h860am"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-3-line" {...props}></Icon>
