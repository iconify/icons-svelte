<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyl6qzb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyl6qzb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:layout-10-fill" {...props}></Icon>
