<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-seb4bin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-seb4bin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice" {...props}></Icon>
