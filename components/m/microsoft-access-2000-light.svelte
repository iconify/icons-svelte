<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ec-0r3lvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ec-0r3lvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-access-2000-light" {...props}></Icon>
