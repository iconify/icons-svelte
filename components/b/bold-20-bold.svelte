<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eysowxhrp.css';
import '../../css/s/seio_1p-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eysowxhrp"/><path class="seio_1p-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bold-20-bold" {...props}></Icon>
