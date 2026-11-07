<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydzcg6vpe.css';
import '../../css/m/m20a56bvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydzcg6vpe"/><path clip-rule="evenodd" class="m20a56bvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:point-on-map-bold" {...props}></Icon>
