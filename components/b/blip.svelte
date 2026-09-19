<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5iwdvbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":488};
const content = `<path class="m5iwdvbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:blip" {...props}></Icon>
