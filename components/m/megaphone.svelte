<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4hs4hvwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":520,"height":464};
const content = `<path class="w4hs4hvwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:megaphone" {...props}></Icon>
