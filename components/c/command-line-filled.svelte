<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6lgoib4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6lgoib4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:command-line-filled" {...props}></Icon>
