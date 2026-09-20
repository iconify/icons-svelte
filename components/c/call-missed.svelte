<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m56y2klmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m56y2klmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:call-missed" {...props}></Icon>
