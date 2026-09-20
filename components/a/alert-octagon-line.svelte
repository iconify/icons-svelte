<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhi4-9wtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhi4-9wtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alert-octagon-line" {...props}></Icon>
