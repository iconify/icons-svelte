<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxivi6frs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kxivi6frs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:compact-disc-filled" {...props}></Icon>
