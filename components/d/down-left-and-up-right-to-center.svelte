<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8tk3xbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x8tk3xbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:down-left-and-up-right-to-center" {...props}></Icon>
