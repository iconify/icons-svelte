<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z21hsdbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z21hsdbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:enphase-light" {...props}></Icon>
