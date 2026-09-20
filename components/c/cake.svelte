<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tsi_6bc7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="tsi_6bc7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:cake" {...props}></Icon>
