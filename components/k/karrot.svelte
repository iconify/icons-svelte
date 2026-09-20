<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts8chuoof.css';
import '../../css/h/hqufffsil.css';
import '../../css/v/ves5g3ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ts8chuoof"/><path class="hqufffsil"/><path class="ves5g3ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:karrot" {...props}></Icon>
