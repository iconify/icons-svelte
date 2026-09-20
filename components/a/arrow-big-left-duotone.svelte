<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tawu72kpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tawu72kpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-left-duotone" {...props}></Icon>
