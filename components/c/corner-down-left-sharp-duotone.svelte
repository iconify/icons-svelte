<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skkqfibng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skkqfibng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:corner-down-left-sharp-duotone" {...props}></Icon>
