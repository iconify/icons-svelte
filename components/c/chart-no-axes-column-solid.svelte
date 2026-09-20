<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvpi71b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvpi71b7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-no-axes-column-solid" {...props}></Icon>
