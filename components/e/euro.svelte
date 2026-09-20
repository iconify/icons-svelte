<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0h91irzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k0h91irzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:euro" {...props}></Icon>
