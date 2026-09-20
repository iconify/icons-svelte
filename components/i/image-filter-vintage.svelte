<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oncd8qu5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oncd8qu5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-filter-vintage" {...props}></Icon>
