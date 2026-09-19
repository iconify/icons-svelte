<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm0h_i9fz.css';
import '../../css/g/gt-wt7bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bm0h_i9fz"/><path class="gt-wt7bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ice-cream-sharp" {...props}></Icon>
