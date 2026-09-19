<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-g68ybph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-g68ybph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-tumblr" {...props}></Icon>
