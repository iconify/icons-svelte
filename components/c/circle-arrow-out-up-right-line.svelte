<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh268tzqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh268tzqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-arrow-out-up-right-line" {...props}></Icon>
