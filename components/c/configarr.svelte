<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfe2xe1gr.css';
import '../../css/b/bstbd176c.css';
import '../../css/d/ds69pvbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zfe2xe1gr"/><path class="bstbd176c"/><path class="ds69pvbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:configarr" {...props}></Icon>
