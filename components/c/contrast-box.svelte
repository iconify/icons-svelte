<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f10q95yyd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f10q95yyd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:contrast-box" {...props}></Icon>
