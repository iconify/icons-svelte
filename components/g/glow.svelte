<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdti4s_xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdti4s_xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:glow" {...props}></Icon>
