<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axqt_ft5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axqt_ft5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:laptop-mac" {...props}></Icon>
