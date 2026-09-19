<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k585igbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k585igbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:euro" {...props}></Icon>
