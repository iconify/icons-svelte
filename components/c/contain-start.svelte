<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5bheobsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5bheobsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:contain-start" {...props}></Icon>
