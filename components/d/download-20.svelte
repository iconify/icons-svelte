<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn4hkfpso.css';
import '../../css/e/e1cs2-20w.css';
import '../../css/x/x72zhtbvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dn4hkfpso"/><path class="e1cs2-20w"/><path class="x72zhtbvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:download-20" {...props}></Icon>
