<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuv1kqflf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cuv1kqflf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:goatcounter" {...props}></Icon>
