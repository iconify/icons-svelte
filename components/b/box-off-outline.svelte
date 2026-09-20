<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk-ld7kbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk-ld7kbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-off-outline" {...props}></Icon>
