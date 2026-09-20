<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0x3uhbzd.css';
import '../../css/l/lo8henb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g0x3uhbzd"/><path class="lo8henb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:red-hat" {...props}></Icon>
