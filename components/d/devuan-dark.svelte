<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gt31zyczs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gt31zyczs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:devuan-dark" {...props}></Icon>
