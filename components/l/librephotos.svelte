<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydwt8bbeh.css';
import '../../css/x/x5xtfzb4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ydwt8bbeh"/><path class="x5xtfzb4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:librephotos" {...props}></Icon>
