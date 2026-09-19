<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p677pebfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p677pebfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:metube" {...props}></Icon>
