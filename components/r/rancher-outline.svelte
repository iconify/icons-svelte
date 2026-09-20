<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xii50qbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xii50qbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rancher-outline" {...props}></Icon>
