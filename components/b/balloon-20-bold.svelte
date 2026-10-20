<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx1ri5b_k.css';
import '../../css/v/v9p5ihx-c.css';
import '../../css/g/gd_6nq8xf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yx1ri5b_k"/><path class="v9p5ihx-c"/><path class="gd_6nq8xf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:balloon-20-bold" {...props}></Icon>
