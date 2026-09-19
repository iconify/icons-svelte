<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vc6kqfbhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vc6kqfbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:bulb-spot-off" {...props}></Icon>
