<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmla6cb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmla6cb4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:local-car-wash" {...props}></Icon>
