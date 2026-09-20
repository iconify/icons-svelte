<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3c57fbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3c57fbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:egg-crack-line" {...props}></Icon>
