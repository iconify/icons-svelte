<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh1ivl7mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh1ivl7mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-to-up-fill" {...props}></Icon>
