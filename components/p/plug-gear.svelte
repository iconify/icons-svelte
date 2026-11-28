<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdr48f5mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdr48f5mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:plug-gear" {...props}></Icon>
