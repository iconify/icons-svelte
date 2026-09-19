<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3l_pqbpb.css';
import '../../css/l/lkwmxcc_x.css';
import '../../css/n/nsfh04bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3l_pqbpb"/><path class="lkwmxcc_x"/><path class="nsfh04bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:football-pitch-filled" {...props}></Icon>
