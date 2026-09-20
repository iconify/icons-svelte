<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tguvsp97z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tguvsp97z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ironmount" {...props}></Icon>
