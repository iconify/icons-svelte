<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj_2k2vxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lj_2k2vxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:office-building-check" {...props}></Icon>
