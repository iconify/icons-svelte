<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hh1auqbgw.css';
import '../../css/u/uguz_8b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hh1auqbgw"/><path class="uguz_8b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:monica" {...props}></Icon>
