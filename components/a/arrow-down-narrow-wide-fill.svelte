<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wz55x2b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wz55x2b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-down-narrow-wide-fill" {...props}></Icon>
