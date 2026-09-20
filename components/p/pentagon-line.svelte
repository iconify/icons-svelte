<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0-g18vbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0-g18vbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pentagon-line" {...props}></Icon>
