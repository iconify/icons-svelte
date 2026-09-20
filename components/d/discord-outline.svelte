<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw3gh1bmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gw3gh1bmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:discord-outline" {...props}></Icon>
