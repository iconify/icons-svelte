<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-yi1kzxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-yi1kzxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-arrow-down" {...props}></Icon>
