<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uevae-bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uevae-bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:heart" {...props}></Icon>
