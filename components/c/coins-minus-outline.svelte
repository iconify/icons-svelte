<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjtkc_n8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjtkc_n8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:coins-minus-outline" {...props}></Icon>
