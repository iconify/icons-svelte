<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtt7155uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtt7155uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:equipment-gym-03" {...props}></Icon>
