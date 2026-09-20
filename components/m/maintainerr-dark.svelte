<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4kr_v9pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z4kr_v9pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:maintainerr-dark" {...props}></Icon>
