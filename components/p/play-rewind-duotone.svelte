<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7kd-cczz.css';
import '../../css/l/lvinadbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7kd-cczz"/><path class="lvinadbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:play-rewind-duotone" {...props}></Icon>
