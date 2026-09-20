<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b00hsobhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b00hsobhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refund-dollar-line" {...props}></Icon>
