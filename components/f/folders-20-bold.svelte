<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw71h2bxe.css';
import '../../css/x/xkiivi_oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gw71h2bxe"/><path class="xkiivi_oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folders-20-bold" {...props}></Icon>
