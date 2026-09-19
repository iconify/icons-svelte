<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4z47fb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="s4z47fb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:grin-alt" {...props}></Icon>
