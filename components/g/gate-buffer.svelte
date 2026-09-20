<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t82-41b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t82-41b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gate-buffer" {...props}></Icon>
