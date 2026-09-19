<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lad5g161t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lad5g161t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:email" {...props}></Icon>
