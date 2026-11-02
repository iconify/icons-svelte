<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-f5fbcbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-f5fbcbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airpods-line" {...props}></Icon>
