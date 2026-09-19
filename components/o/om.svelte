<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p11hvf2oa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p11hvf2oa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:om" {...props}></Icon>
