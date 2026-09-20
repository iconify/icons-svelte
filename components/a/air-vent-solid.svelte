<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttqym4bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ttqym4bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:air-vent-solid" {...props}></Icon>
