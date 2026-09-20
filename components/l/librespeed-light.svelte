<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oualg3bdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oualg3bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librespeed-light" {...props}></Icon>
