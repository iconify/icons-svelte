<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv7r5pu1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="pv7r5pu1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:chevron-right-bar" {...props}></Icon>
