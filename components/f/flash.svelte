<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt2kzbb-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":216,"height":432};
const content = `<path class="gt2kzbb-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flash" {...props}></Icon>
