<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skq90mbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skq90mbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:marquee-off" {...props}></Icon>
