<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmsoejb8x.css';
import '../../css/z/zltcmzqac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmsoejb8x"/><circle class="zltcmzqac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cadenza" {...props}></Icon>
