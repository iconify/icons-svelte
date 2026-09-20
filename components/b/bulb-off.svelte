<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gm_my446l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gm_my446l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bulb-off" {...props}></Icon>
