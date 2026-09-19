<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr4i-mvju.css';
import '../../css/p/pqy87ebie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zr4i-mvju"/><path class="pqy87ebie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:raisedhandsfingerssplayed" {...props}></Icon>
