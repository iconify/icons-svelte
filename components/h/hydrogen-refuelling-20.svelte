<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr0clkknd.css';
import '../../css/b/bhhnh4bmp.css';
import '../../css/k/k_3z1lbzk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zr0clkknd"/><path class="bhhnh4bmp"/><path class="k_3z1lbzk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-refuelling-20" {...props}></Icon>
