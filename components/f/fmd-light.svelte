<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0ai2gp-g.css';
import '../../css/p/phudelb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g0ai2gp-g"/><path class="phudelb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fmd-light" {...props}></Icon>
