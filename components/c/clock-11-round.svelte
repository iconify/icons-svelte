<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt84qfb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xt84qfb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:clock-11-round" {...props}></Icon>
