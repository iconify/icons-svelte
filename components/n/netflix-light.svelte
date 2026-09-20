<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfoyfdche.css';
import '../../css/i/irfq_r8uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qfoyfdche"/><path class="irfq_r8uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netflix-light" {...props}></Icon>
