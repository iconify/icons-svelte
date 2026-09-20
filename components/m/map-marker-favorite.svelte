<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxjua4cse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxjua4cse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-marker-favorite" {...props}></Icon>
