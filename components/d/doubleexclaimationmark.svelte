<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox8i1rs_p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ox8i1rs_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:doubleexclaimationmark" {...props}></Icon>
