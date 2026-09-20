<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdyn042hz.css';
import '../../css/l/lopv05qtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdyn042hz"/><path class="lopv05qtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nimtable-dark" {...props}></Icon>
