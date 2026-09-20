<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0xxt-34c.css';
import '../../css/f/f2cq9cczx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0xxt-34c"/><path class="f2cq9cczx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mask-happly-bold-duotone" {...props}></Icon>
