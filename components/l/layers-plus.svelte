<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjh8g_qnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xjh8g_qnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:layers-plus" {...props}></Icon>
