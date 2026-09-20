<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/d/d3s5lw5wz.css';
import '../../css/b/b2k2a-inc.css';
import '../../css/p/p9vr9ac7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><path class="d3s5lw5wz"/><path class="b2k2a-inc"/><path class="p9vr9ac7s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:database" {...props}></Icon>
