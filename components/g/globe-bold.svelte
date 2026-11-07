<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iik--rn3y.css';
import '../../css/t/t8sc6ex9y.css';
import '../../css/n/n90j2x48z.css';
import '../../css/t/tnuzmj_om.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iik--rn3y"/><path class="t8sc6ex9y"/><path class="n90j2x48z"/><path class="tnuzmj_om"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:globe-bold" {...props}></Icon>
