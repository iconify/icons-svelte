<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz84-znwv.css';
import '../../css/l/lxe7e-j4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz84-znwv"/><path class="lxe7e-j4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:play-circle-stroke-add-filled" {...props}></Icon>
