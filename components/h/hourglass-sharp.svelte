<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7pn04bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7pn04bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:hourglass-sharp" {...props}></Icon>
