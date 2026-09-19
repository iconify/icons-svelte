<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0gvi5b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0gvi5b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:border-style-dotted" {...props}></Icon>
