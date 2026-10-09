<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiwgf_byw.css';
import '../../css/c/ci54x0bdq.css';
import '../../css/z/zng18pbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fiwgf_byw"/><path class="ci54x0bdq"/><path class="zng18pbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cupcake-20" {...props}></Icon>
