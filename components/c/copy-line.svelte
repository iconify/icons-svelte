<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/joa-7ibra.css';
import '../../css/p/pgshgrb4e.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 joa-7ibra"/><path class="clr-i-outline clr-i-outline-path-2 pgshgrb4e"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:copy-line" {...props}></Icon>
