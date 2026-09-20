<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fea_d8t0e.css';
import '../../css/i/if3pd-1ww.css';
import '../../css/a/a6rqpnekf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fea_d8t0e"/><path class="if3pd-1ww"/><path class="a6rqpnekf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:black-octagon" {...props}></Icon>
