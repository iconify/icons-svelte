<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnix5mb_n.css';
import '../../css/f/fvm61b_7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pnix5mb_n"/><path class="fvm61b_7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ackify" {...props}></Icon>
