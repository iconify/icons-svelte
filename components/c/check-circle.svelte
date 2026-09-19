<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwkw3-cho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwkw3-cho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:check-circle" {...props}></Icon>
