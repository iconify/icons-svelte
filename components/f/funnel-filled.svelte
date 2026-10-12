<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj2x0ebtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qj2x0ebtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:funnel-filled" {...props}></Icon>
