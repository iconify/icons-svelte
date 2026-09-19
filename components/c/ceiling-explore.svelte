<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssc2c_b5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssc2c_b5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-explore" {...props}></Icon>
