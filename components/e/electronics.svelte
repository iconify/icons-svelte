<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fq0zzwbhy.css';
import '../../css/o/omdctlxyb.css';
import '../../css/u/uwk-mk2ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fq0zzwbhy"/><path class="omdctlxyb"/><path class="uwk-mk2ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:electronics" {...props}></Icon>
