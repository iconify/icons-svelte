<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwqqdqbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="nwqqdqbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-pharmacy" {...props}></Icon>
