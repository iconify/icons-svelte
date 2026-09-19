<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wem_b1dpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wem_b1dpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:facebook-stroke-12" {...props}></Icon>
