<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7201fbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7201fbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:abstract-filled" {...props}></Icon>
