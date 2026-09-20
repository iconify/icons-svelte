<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km8oqva3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="km8oqva3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pokeball" {...props}></Icon>
