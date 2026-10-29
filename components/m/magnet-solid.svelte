<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmjpvjb1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmjpvjb1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:magnet-solid" {...props}></Icon>
