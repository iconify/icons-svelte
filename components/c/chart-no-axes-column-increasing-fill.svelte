<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdntu4bcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fdntu4bcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-no-axes-column-increasing-fill" {...props}></Icon>
