<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snniw392r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="snniw392r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bluetooth-line" {...props}></Icon>
