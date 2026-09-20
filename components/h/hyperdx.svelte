<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7_p-eb5l.css';
import '../../css/l/lx1hlcb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t7_p-eb5l"/><path class="lx1hlcb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hyperdx" {...props}></Icon>
