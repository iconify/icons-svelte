<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir1z2yyne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="ir1z2yyne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:chevron-left" {...props}></Icon>
