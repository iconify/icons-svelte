<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt26bdcbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zt26bdcbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:house-alert-outline" {...props}></Icon>
