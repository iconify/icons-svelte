<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3q3ev6-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3q3ev6-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:meter-gas" {...props}></Icon>
