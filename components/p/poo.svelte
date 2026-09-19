<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amk3b5brs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amk3b5brs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:poo" {...props}></Icon>
