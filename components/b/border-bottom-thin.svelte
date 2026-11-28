<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amns3_b5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="amns3_b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-bottom-thin" {...props}></Icon>
