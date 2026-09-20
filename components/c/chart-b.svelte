<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6yfbr_kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6yfbr_kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-b" {...props}></Icon>
