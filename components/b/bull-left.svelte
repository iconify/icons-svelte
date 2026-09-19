<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5py72b_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t5py72b_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bull-left" {...props}></Icon>
