<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ax89p-b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ax89p-b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:necklace" {...props}></Icon>
