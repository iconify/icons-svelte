<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q44wy-m0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q44wy-m0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:crosshairs" {...props}></Icon>
