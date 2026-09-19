<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q02x0dbpu.css';
import '../../css/j/jupl2yb5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q02x0dbpu"/><path class="jupl2yb5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:coreui" {...props}></Icon>
