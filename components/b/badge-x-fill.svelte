<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x42n11b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x42n11b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badge-x-fill" {...props}></Icon>
