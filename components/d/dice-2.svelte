<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jds0_5bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jds0_5bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:dice-2" {...props}></Icon>
