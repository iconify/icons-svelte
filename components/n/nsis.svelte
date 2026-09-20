<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn8tvia-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mn8tvia-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:nsis" {...props}></Icon>
