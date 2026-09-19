<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k72q-yb3f.css';
import '../../css/d/dd34srmzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k72q-yb3f"/><path class="dd34srmzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:golf-alt" {...props}></Icon>
