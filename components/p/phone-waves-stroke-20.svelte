<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yj208ackd.css';
import '../../css/r/r_67kbawa.css';
import '../../css/q/qlene92hf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yj208ackd"/><path class="r_67kbawa"/><path class="qlene92hf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-waves-stroke-20" {...props}></Icon>
