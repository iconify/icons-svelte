<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guvsaeb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="guvsaeb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:reorder-two-sharp" {...props}></Icon>
