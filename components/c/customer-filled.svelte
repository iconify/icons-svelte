<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lflbifr_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="lflbifr_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:customer-filled" {...props}></Icon>
