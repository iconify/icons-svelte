<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bri3tmb-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bri3tmb-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:freecodecamp" {...props}></Icon>
