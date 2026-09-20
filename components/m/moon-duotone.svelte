<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrqy14fcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrqy14fcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:moon-duotone" {...props}></Icon>
