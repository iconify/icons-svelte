<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp8d2ookr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yp8d2ookr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gift-card-fill" {...props}></Icon>
