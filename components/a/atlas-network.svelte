<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbvvl1bla.css';
import '../../css/t/thpm74blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="wbvvl1bla"/><path class="thpm74blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atlas-network" {...props}></Icon>
