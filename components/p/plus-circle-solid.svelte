<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cekqefb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="cekqefb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:plus-circle-solid" {...props}></Icon>
