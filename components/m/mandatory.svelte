<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eob2i8v4o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eob2i8v4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mandatory" {...props}></Icon>
