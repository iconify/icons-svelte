<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjeey1y5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjeey1y5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-3x3" {...props}></Icon>
