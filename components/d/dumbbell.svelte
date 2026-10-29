<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nee5k0bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nee5k0bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:dumbbell" {...props}></Icon>
