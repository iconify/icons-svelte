<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hye3s26us.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hye3s26us"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:male-sharp" {...props}></Icon>
