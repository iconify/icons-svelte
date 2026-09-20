<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ooi09cc0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ooi09cc0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:box-arrow-up-outline" {...props}></Icon>
