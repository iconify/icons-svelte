<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv7o_0b3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dv7o_0b3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ribbon-health" {...props}></Icon>
