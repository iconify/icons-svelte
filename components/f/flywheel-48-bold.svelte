<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oum63jbgm.css';
import '../../css/d/dg95q9b0l.css';
import '../../css/g/g7b-z_b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oum63jbgm"/><path class="dg95q9b0l"/><path class="g7b-z_b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flywheel-48-bold" {...props}></Icon>
