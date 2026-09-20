<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jwaujx.css';
import '../../css/y/ydovum.css';
import '../../css/x/xopa8c.css';
import '../../css/f/fill-to-0.css';
import '../../css/s/so-from-48.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2_5px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jwaujx ydovum"/><circle class="xopa8c ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:map-marker-twotone" {...props}></Icon>
