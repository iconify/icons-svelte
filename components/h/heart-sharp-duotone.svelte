<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlcuecc1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlcuecc1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:heart-sharp-duotone" {...props}></Icon>
