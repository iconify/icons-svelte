<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itd-o_bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itd-o_bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:binge" {...props}></Icon>
