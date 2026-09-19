<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5h4td7le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5h4td7le"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bentley" {...props}></Icon>
