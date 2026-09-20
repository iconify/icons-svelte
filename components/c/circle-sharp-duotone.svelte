<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmpez3udl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vmpez3udl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-sharp-duotone" {...props}></Icon>
