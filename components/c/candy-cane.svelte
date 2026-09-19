<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ms3g9iieh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ms3g9iieh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:candy-cane" {...props}></Icon>
