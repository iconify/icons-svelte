<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r10zx7mmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r10zx7mmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gocd" {...props}></Icon>
