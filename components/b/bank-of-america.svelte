<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud4tzydmp.css';
import '../../css/v/vj4zwzbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ud4tzydmp"/><path class="vj4zwzbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bank-of-america" {...props}></Icon>
