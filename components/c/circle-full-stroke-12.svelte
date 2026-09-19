<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4i59nbxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<circle class="l4i59nbxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:circle-full-stroke-12" {...props}></Icon>
