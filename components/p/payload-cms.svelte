<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlbf1yb1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlbf1yb1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:payload-cms" {...props}></Icon>
