<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu424ublx.css';
import '../../css/f/f5bqv3-2b.css';
import '../../css/k/kem81wb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wu424ublx"/><path class="f5bqv3-2b"/><path class="kem81wb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-minus-48" {...props}></Icon>
