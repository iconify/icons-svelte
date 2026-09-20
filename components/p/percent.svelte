<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4k4dsb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c4k4dsb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:percent" {...props}></Icon>
