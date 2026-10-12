<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri--i_b-k.css';
import '../../css/v/vg2qp3oat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ri--i_b-k"/><path class="vg2qp3oat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cloud-sun-fill-20" {...props}></Icon>
