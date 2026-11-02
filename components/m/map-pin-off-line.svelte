<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nox5ngbqv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nox5ngbqv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-off-line" {...props}></Icon>
