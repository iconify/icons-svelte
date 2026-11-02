<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzav2tbjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzav2tbjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-circle-dash-fill" {...props}></Icon>
