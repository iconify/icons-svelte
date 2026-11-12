<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5ledtbof.css';
import '../../css/v/vtrz5wtxj.css';
import '../../css/m/mx9-r4b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q5ledtbof"/><path class="vtrz5wtxj"/><path class="mx9-r4b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:leafwiki-dark" {...props}></Icon>
