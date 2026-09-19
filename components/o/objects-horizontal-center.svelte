<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jib_m7btj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jib_m7btj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:objects-horizontal-center" {...props}></Icon>
