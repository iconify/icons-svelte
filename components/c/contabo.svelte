<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rebv2ackv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rebv2ackv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:contabo" {...props}></Icon>
