<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cht574biq.css';
import '../../css/y/yhb26obxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cht574biq"/><path class="yhb26obxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reactor-48" {...props}></Icon>
