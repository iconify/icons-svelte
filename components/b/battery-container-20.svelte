<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpn7eesli.css';
import '../../css/v/v_25zwbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mpn7eesli"/><path class="v_25zwbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-container-20" {...props}></Icon>
