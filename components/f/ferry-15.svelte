<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grf4dx6ip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="grf4dx6ip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:ferry-15" {...props}></Icon>
