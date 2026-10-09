<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so2mw5bhs.css';
import '../../css/n/nnuycobpf.css';
import '../../css/n/ney70wbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="so2mw5bhs"/><path class="nnuycobpf"/><path class="ney70wbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mountain-river-20-bold" {...props}></Icon>
