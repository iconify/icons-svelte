<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/tfgra3ble.css';
import '../../css/b/b8muav1zi.css';
import '../../css/u/utnv9fgpg.css';
import '../../css/j/jlzv4qbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="tfgra3ble"/><path class="b8muav1zi"/><path class="utnv9fgpg"/><path class="jlzv4qbob"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mug-linear" {...props}></Icon>
