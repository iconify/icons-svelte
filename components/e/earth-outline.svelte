<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/er2fz3ono.css';
import '../../css/l/lwb5t-h6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="er2fz3ono"/><path class="lwb5t-h6o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:earth-outline" {...props}></Icon>
