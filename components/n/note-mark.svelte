<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsxw_objg.css';
import '../../css/w/w_fbcy7gw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xsxw_objg"/><path class="w_fbcy7gw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:note-mark" {...props}></Icon>
