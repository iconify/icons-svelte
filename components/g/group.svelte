<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufiednfxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufiednfxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:group" {...props}></Icon>
