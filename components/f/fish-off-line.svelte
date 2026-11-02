<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/je9vfbbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="je9vfbbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fish-off-line" {...props}></Icon>
