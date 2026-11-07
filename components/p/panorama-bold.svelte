<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5qmym-cz.css';
import '../../css/i/iln029b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5qmym-cz"/><path clip-rule="evenodd" class="iln029b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panorama-bold" {...props}></Icon>
