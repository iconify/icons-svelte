<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uao18mj6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uao18mj6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airpods-2-line" {...props}></Icon>
