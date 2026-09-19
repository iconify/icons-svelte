<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6i_d-b2e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t6i_d-b2e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:moon" {...props}></Icon>
