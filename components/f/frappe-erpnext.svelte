<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ntug3ea9g.css';
import '../../css/y/y6g7tfbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ntug3ea9g"/><path class="y6g7tfbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-erpnext" {...props}></Icon>
