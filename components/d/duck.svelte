<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/um721dv4z.css';
import '../../css/w/w96bn_bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="um721dv4z"/><path class="w96bn_bsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:duck" {...props}></Icon>
