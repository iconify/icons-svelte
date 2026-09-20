<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rbu14lbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rbu14lbvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:retro-achievements" {...props}></Icon>
