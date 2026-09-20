<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmy4j9b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmy4j9b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:map-sharp" {...props}></Icon>
