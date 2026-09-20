<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0t5hu09k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k0t5hu09k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:basic-memory-dark" {...props}></Icon>
