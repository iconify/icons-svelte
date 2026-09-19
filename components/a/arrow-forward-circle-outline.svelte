<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xobthpb_z.css';
import '../../css/l/ld5kc0m-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xobthpb_z"/><path class="ld5kc0m-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-forward-circle-outline" {...props}></Icon>
