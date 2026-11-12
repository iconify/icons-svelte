<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w71383bwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w71383bwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:keyhelp-dark" {...props}></Icon>
