<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pni5u1bji.css';
import '../../css/h/hv0sd2vvm.css';
import '../../css/w/w550r6lgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pni5u1bji"/><path class="hv0sd2vvm"/><path class="w550r6lgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-river-48-bold" {...props}></Icon>
