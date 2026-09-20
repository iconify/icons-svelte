<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh63xupey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xh63xupey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gauge-full" {...props}></Icon>
