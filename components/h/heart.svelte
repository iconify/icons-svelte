<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gluszrb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gluszrb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart" {...props}></Icon>
