<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxa_324eo.css';
import '../../css/s/s79t828hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxa_324eo"/><circle class="s79t828hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:bd-1x1" {...props}></Icon>
