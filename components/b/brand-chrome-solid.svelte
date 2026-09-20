<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_xr5ysjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e_xr5ysjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:brand-chrome-solid" {...props}></Icon>
