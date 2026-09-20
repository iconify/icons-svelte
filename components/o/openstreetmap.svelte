<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq2wkoc3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq2wkoc3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openstreetmap" {...props}></Icon>
