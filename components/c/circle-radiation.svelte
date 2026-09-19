<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2n6r838m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w2n6r838m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-radiation" {...props}></Icon>
