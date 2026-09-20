<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbpz_ob3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xbpz_ob3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:evsy-light" {...props}></Icon>
