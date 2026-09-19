<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqr5b_7bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pqr5b_7bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:pint" {...props}></Icon>
