<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5z8iib0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5z8iib0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:br1" {...props}></Icon>
