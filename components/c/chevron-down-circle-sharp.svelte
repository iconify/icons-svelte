<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctl2aebre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ctl2aebre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:chevron-down-circle-sharp" {...props}></Icon>
