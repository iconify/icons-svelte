<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb_ogzbcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":1027};
const content = `<path class="fb_ogzbcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alertpay" {...props}></Icon>
