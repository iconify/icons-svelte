<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rym_01uyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rym_01uyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lecture" {...props}></Icon>
