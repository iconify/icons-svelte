<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz1otrbai.css';
import '../../css/e/eka_oeb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gz1otrbai"/><path class="eka_oeb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:calagopus" {...props}></Icon>
