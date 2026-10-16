<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc46o1p0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xc46o1p0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:insurance-48-bold" {...props}></Icon>
