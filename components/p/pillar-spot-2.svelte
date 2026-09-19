<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4u-8pacx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4u-8pacx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pillar-spot-2" {...props}></Icon>
