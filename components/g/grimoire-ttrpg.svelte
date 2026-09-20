<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_eg9t9sm.css';
import '../../css/m/mw3jqjowb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r_eg9t9sm"/><path class="mw3jqjowb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grimoire-ttrpg" {...props}></Icon>
