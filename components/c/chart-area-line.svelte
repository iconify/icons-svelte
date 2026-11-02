<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unqr9nb2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unqr9nb2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-area-line" {...props}></Icon>
