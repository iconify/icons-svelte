<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywn-wqhib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ywn-wqhib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:maintenance-warning" {...props}></Icon>
