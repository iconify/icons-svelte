<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzm9fwb_a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzm9fwb_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-t1" {...props}></Icon>
