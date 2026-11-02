<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsz_46bkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tsz_46bkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:process-line" {...props}></Icon>
