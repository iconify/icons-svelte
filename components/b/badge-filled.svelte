<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xr2u00bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xr2u00bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:badge-filled" {...props}></Icon>
