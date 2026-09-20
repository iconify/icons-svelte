<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piz8b0-cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="piz8b0-cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cup-liquid" {...props}></Icon>
