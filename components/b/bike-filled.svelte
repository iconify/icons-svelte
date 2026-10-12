<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm73iyntv.css';
import '../../css/y/ywrez9dnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pm73iyntv"/><path class="ywrez9dnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bike-filled" {...props}></Icon>
