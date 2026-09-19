<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmj_l2fxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmj_l2fxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:eject" {...props}></Icon>
