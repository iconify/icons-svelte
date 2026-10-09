<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxqh80bxh.css';
import '../../css/n/nxwt419zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mxqh80bxh"/><path class="nxwt419zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-conditioning-20" {...props}></Icon>
