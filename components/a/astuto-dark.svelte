<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggsd3sdap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ggsd3sdap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:astuto-dark" {...props}></Icon>
