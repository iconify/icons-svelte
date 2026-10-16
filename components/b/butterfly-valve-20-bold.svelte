<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/barf7s2gy.css';
import '../../css/d/dkfqdrm2d.css';
import '../../css/g/g4dwobbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="barf7s2gy"/><path class="dkfqdrm2d"/><path class="g4dwobbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:butterfly-valve-20-bold" {...props}></Icon>
