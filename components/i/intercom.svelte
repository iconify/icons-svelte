<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z38gfkbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="z38gfkbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:intercom" {...props}></Icon>
