<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogv3zac7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ogv3zac7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:hyperbolic" {...props}></Icon>
