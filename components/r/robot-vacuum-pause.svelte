<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tph2u6z3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tph2u6z3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:robot-vacuum-pause" {...props}></Icon>
