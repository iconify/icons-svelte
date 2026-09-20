<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m067-7bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m067-7bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circuit-switch-closed" {...props}></Icon>
