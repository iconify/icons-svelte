<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq_y6cb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":512};
const content = `<path class="iq_y6cb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:backpack" {...props}></Icon>
