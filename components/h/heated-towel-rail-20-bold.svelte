<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3onifb8e.css';
import '../../css/n/n9vml882r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z3onifb8e"/><path class="n9vml882r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heated-towel-rail-20-bold" {...props}></Icon>
