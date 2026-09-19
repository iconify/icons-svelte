<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si4d4hb_u.css';
import '../../css/y/yv_brepse.css';
import '../../css/f/f33c5bbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="si4d4hb_u"/><path class="yv_brepse"/><path class="f33c5bbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:down-circle-twotone" {...props}></Icon>
