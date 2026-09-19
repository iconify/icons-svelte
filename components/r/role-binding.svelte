<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzkun1bgf.css';
import '../../css/m/m5u32yv6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzkun1bgf"/><path class="m5u32yv6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:role-binding" {...props}></Icon>
