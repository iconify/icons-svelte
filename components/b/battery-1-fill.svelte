<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq8vp4b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq8vp4b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:battery-1-fill" {...props}></Icon>
