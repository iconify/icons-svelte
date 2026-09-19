<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5s5ez1oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w5s5ez1oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:git-pull-request" {...props}></Icon>
