<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrytxqbtb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrytxqbtb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:egg-line" {...props}></Icon>
