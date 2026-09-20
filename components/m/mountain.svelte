<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyg_l4nkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cyg_l4nkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:mountain" {...props}></Icon>
