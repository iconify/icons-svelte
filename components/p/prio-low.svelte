<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zplot3v2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zplot3v2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:prio-low" {...props}></Icon>
