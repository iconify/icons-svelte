<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3d3vt4lo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3d3vt4lo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:back-square-filled" {...props}></Icon>
