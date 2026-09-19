<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_k3-08ur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="r_k3-08ur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:car-on" {...props}></Icon>
