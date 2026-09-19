<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvk4ocgpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvk4ocgpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:arrow-circle-up-right" {...props}></Icon>
