<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_rns8jjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b_rns8jjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:balloon-sharp" {...props}></Icon>
