<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_gmhcswf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_gmhcswf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-question" {...props}></Icon>
