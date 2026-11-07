<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3dnrk_0v.css';
import '../../css/y/ywc-2eb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z3dnrk_0v"/><path class="ywc-2eb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-bold-duotone" {...props}></Icon>
