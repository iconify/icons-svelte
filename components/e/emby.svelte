<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg_rohbjm.css';
import '../../css/c/cdq24z_9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jg_rohbjm"/><path class="cdq24z_9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:emby" {...props}></Icon>
