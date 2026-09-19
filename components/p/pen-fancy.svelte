<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olsnwmrvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="olsnwmrvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:pen-fancy" {...props}></Icon>
