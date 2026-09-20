<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af3h010ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af3h010ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:diving-scuba-tank-multiple" {...props}></Icon>
