<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ia11uwb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ia11uwb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:reorder-four-sharp" {...props}></Icon>
