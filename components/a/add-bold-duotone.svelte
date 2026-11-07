<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yaoyf82ot.css';
import '../../css/v/vmj_u5b4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yaoyf82ot"/><path class="vmj_u5b4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:add-bold-duotone" {...props}></Icon>
