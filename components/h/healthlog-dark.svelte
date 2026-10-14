<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2ftmugmu.css';
import '../../css/t/t2zrok28c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x2ftmugmu"/><path class="t2zrok28c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:healthlog-dark" {...props}></Icon>
