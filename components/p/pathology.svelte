<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sll1r44eb.css';
import '../../css/m/mr5-0kkhw.css';
import '../../css/c/cz6_nbepy.css';
import '../../css/p/pvctzfblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="sll1r44eb"/><path class="mr5-0kkhw"/><path class="cz6_nbepy"/><path class="pvctzfblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:pathology" {...props}></Icon>
