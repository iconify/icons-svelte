<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at71zhbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="at71zhbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:rose-sharp" {...props}></Icon>
