<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka4u2_gho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ka4u2_gho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:checkmark-circle-sharp" {...props}></Icon>
