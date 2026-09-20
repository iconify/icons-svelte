<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdiilpxab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdiilpxab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:radio-handheld" {...props}></Icon>
