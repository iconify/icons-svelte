<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1vmbtb-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":384};
const content = `<path class="l1vmbtb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:check-all" {...props}></Icon>
