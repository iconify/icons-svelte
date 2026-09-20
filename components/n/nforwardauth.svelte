<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs8qhvbzx.css';
import '../../css/m/mueojzrmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qs8qhvbzx"/><path class="mueojzrmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nforwardauth" {...props}></Icon>
