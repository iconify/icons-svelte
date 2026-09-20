<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9885dbli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s9885dbli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:jupyter" {...props}></Icon>
