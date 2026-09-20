<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkc2gm92p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkc2gm92p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:nextjs" {...props}></Icon>
