<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbxm3usqn.css';
import '../../css/l/lzg5bgbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="wbxm3usqn"/><path class="lzg5bgbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbwhois" {...props}></Icon>
