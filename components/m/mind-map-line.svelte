<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a177edbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a177edbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mind-map-line" {...props}></Icon>
