<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g88jb2prf.css';
import '../../css/s/s7tj_nz1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g88jb2prf"/><path class="s7tj_nz1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-line" {...props}></Icon>
