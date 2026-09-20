<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh4pb2kax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gh4pb2kax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:photon" {...props}></Icon>
