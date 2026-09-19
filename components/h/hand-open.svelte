<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l7sprv35n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="l7sprv35n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:hand-open" {...props}></Icon>
