<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owm-0ybmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owm-0ybmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:emergency-flashers-line" {...props}></Icon>
