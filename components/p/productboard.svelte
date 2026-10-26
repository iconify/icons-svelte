<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khc6856kd.css';
import '../../css/o/oel1jvbgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":42};
const content = `<path class="khc6856kd"/><path class="oel1jvbgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:productboard" {...props}></Icon>
