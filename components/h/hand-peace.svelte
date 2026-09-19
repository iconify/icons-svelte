<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlzcbobup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qlzcbobup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hand-peace" {...props}></Icon>
