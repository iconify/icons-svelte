<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l20v2fbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l20v2fbus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coal-20" {...props}></Icon>
