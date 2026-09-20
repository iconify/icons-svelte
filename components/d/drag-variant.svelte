<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhy03hbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhy03hbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:drag-variant" {...props}></Icon>
