<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbelm_byx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vbelm_byx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pin" {...props}></Icon>
