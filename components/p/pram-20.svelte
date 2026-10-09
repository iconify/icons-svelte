<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bcw6mnbls.css';
import '../../css/m/m8t0x9bfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bcw6mnbls"/><path class="m8t0x9bfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pram-20" {...props}></Icon>
