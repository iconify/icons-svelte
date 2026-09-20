<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/io9g4snny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="io9g4snny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pills3-filled" {...props}></Icon>
