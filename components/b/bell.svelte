<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx0ku_hzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":24};
const content = `<path class="lx0ku_hzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:bell" {...props}></Icon>
