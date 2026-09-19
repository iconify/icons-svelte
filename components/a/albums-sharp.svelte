<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drytl15lb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="drytl15lb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:albums-sharp" {...props}></Icon>
