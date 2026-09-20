<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd4a16fbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":25};
const content = `<path class="gd4a16fbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:direction-rtl" {...props}></Icon>
