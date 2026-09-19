<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzxrjhs0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="mzxrjhs0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:laptop-chromebook" {...props}></Icon>
