<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grbzzob4o.css';
import '../../css/t/trg2kib5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grbzzob4o"/><path class="trg2kib5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-round-angle-bold" {...props}></Icon>
