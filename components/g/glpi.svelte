<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5o3f9vcr.css';
import '../../css/w/w_tn9pbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t5o3f9vcr"/><path class="w_tn9pbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glpi" {...props}></Icon>
