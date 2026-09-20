<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu23libwc.css';
import '../../css/a/at1afwblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pu23libwc"/><path class="at1afwblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:disc" {...props}></Icon>
