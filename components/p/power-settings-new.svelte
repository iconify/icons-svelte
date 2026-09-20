<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/py7hu3tca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="py7hu3tca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:power-settings-new" {...props}></Icon>
