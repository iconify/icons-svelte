<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1pfy_bym.css';
import '../../css/f/fsw4fslqf.css';
import '../../css/z/z_svvovos.css';
import '../../css/c/cxc03ab-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s1pfy_bym"/><path class="fsw4fslqf"/><path class="z_svvovos"/><path class="cxc03ab-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-car-20-bold" {...props}></Icon>
