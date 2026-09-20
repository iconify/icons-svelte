<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p700io9zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p700io9zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:maximize6" {...props}></Icon>
