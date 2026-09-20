<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqs2jwb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqs2jwb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-line" {...props}></Icon>
