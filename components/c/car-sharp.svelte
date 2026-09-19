<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bznvht37f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bznvht37f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:car-sharp" {...props}></Icon>
