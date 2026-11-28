<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mei2r4bmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mei2r4bmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:palette-plus" {...props}></Icon>
