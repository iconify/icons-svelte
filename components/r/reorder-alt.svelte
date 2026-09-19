<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ithfy_p_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ithfy_p_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:reorder-alt" {...props}></Icon>
