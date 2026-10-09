<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnd4qacir.css';
import '../../css/x/x43eb82dg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tnd4qacir"/><path class="x43eb82dg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hot-dog-20-bold" {...props}></Icon>
