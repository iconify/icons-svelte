<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/msy05x8yd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="msy05x8yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-right-line" {...props}></Icon>
