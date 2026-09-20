<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0a56fpvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0a56fpvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copy-2-fill" {...props}></Icon>
