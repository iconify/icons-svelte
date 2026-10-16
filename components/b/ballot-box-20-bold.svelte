<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufl2bny3v.css';
import '../../css/e/eay9adclz.css';
import '../../css/t/tf2yhvbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ufl2bny3v"/><path class="eay9adclz"/><path class="tf2yhvbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ballot-box-20-bold" {...props}></Icon>
