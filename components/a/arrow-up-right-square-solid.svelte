<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0dw-9b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h0dw-9b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:arrow-up-right-square-solid" {...props}></Icon>
