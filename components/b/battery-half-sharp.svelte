<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt57vq-0m.css';
import '../../css/i/iorf33r0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wt57vq-0m"/><path class="iorf33r0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:battery-half-sharp" {...props}></Icon>
