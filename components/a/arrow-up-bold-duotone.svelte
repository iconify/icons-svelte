<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyjanl8xm.css';
import '../../css/l/l-7l4bc0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xyjanl8xm"/><path class="l-7l4bc0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-bold-duotone" {...props}></Icon>
