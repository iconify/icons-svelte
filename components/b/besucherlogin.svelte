<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um7_4ac7p.css';
import '../../css/k/kfueumbyk.css';
import '../../css/p/p98w-ymbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="um7_4ac7p"/><rect class="kfueumbyk"/><path class="p98w-ymbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:besucherlogin" {...props}></Icon>
