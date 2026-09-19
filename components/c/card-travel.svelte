<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdi5s9ivd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="kdi5s9ivd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:card-travel" {...props}></Icon>
