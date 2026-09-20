<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1uf_1b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":300,"height":43,"left":-0.835,"top":-0.509};
const content = `<path clip-rule="evenodd" class="f1uf_1b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:astrazeneca" {...props}></Icon>
