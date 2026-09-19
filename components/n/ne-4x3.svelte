<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl1d0s49v.css';
import '../../css/i/ictwwwp8x.css';
import '../../css/c/c2rntjb-m.css';
import '../../css/k/k0_w5cj4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="bl1d0s49v"/><path class="ictwwwp8x"/><path class="c2rntjb-m"/><circle class="k0_w5cj4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:ne-4x3" {...props}></Icon>
