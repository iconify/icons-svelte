<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo_gcl4jc.css';
import '../../css/d/dp0jygg6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oo_gcl4jc"/><path class="dp0jygg6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rackula" {...props}></Icon>
