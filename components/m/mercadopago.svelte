<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjgcf6wck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zjgcf6wck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:mercadopago" {...props}></Icon>
