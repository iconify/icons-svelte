<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcmht4bdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="tcmht4bdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:hq" {...props}></Icon>
