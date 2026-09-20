<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blc_bco-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="blc_bco-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:eye-magnifying-glass" {...props}></Icon>
