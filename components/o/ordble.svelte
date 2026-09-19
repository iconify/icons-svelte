<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbko1l4zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":710,"height":717};
const content = `<path class="wbko1l4zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:ordble" {...props}></Icon>
