<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/caf4w40kg.css';
import '../../css/v/vqmcn9mpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="caf4w40kg"/><path class="vqmcn9mpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:function-argument-ltr" {...props}></Icon>
