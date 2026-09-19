<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwwdm_2ru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fwwdm_2ru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pen-clip" {...props}></Icon>
