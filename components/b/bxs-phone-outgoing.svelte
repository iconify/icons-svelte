<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksaeh52hk.css';
import '../../css/u/uh3okxpvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ksaeh52hk"/><path class="uh3okxpvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-phone-outgoing" {...props}></Icon>
