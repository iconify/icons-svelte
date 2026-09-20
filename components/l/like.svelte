<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqwry21cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqwry21cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:like" {...props}></Icon>
