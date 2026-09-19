<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwvk4z-7p.css';
import '../../css/a/aa_03ls8j.css';
import '../../css/i/iki_14f2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kwvk4z-7p"/><rect class="aa_03ls8j"/><rect class="aa_03ls8j"/><path class="iki_14f2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:print-sharp" {...props}></Icon>
