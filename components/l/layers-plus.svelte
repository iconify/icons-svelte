<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsc6fcarb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xsc6fcarb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:layers-plus" {...props}></Icon>
