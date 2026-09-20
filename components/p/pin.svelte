<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx-k5ebuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dx-k5ebuq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pin" {...props}></Icon>
