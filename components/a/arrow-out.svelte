<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-wtosbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":384};
const content = `<path class="b-wtosbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:arrow-out" {...props}></Icon>
