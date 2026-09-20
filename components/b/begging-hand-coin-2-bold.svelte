<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7pfnoh_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f7pfnoh_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:begging-hand-coin-2-bold" {...props}></Icon>
