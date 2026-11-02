<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vh53_dbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vh53_dbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:copilot-fill" {...props}></Icon>
