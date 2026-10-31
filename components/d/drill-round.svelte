<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h52qjsb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h52qjsb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drill-round" {...props}></Icon>
