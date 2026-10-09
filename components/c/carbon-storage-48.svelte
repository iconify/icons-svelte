<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8mp0wbzm.css';
import '../../css/d/dwl2-5bwr.css';
import '../../css/u/unf30navr.css';
import '../../css/z/zrr3btyck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="m8mp0wbzm"/><path class="dwl2-5bwr"/><path class="unf30navr"/><path class="zrr3btyck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carbon-storage-48" {...props}></Icon>
