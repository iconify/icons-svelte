<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0_3hsgpg.css';
import '../../css/h/hw9pzduln.css';
import '../../css/x/x8hovebwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s0_3hsgpg"/><path class="hw9pzduln"/><path class="x8hovebwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:holyarrs-light" {...props}></Icon>
