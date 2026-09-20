<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq7i1rv2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq7i1rv2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:hcl" {...props}></Icon>
