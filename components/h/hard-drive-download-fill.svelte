<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys3s1y12f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys3s1y12f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hard-drive-download-fill" {...props}></Icon>
