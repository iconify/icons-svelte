<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amae8eb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="amae8eb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:circle" {...props}></Icon>
