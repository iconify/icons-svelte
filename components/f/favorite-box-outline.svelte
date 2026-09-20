<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttz056v2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttz056v2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-box-outline" {...props}></Icon>
