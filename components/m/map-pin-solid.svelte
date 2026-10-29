<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuk4pobuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuk4pobuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:map-pin-solid" {...props}></Icon>
