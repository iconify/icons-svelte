<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dekd_hbaw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dekd_hbaw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cube-spark" {...props}></Icon>
