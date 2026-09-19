<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omvfj0p9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omvfj0p9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:heart-square" {...props}></Icon>
