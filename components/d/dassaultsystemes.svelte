<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruv4d3bww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruv4d3bww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:dassaultsystemes" {...props}></Icon>
