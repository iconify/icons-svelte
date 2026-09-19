<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdkpdlb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wdkpdlb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:key-sharp" {...props}></Icon>
