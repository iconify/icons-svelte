<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t76xesq6f.css';
import '../../css/s/stwi24bsm.css';
import '../../css/i/ip1zolbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t76xesq6f"/><path class="stwi24bsm"/><path class="ip1zolbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rcd-20-bold" {...props}></Icon>
