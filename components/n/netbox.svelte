<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4z4o6b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="s4z4o6b3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:netbox" {...props}></Icon>
