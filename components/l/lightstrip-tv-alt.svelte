<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfwb_gbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfwb_gbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lightstrip-tv-alt" {...props}></Icon>
