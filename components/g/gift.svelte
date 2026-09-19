<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm6ujac-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mm6ujac-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:gift" {...props}></Icon>
