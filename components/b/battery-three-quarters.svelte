<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6qfutqed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="f6qfutqed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:battery-three-quarters" {...props}></Icon>
