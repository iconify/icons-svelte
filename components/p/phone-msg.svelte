<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oprfdnb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="oprfdnb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-msg" {...props}></Icon>
