<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1w4obb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1w4obb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hand-back-left" {...props}></Icon>
