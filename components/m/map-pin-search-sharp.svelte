<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2zdh0bfk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m2zdh0bfk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:map-pin-search-sharp" {...props}></Icon>
