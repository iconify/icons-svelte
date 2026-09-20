<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/geooavbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="geooavbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:drag-horizontal-variant" {...props}></Icon>
