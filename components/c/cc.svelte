<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba9o2nfex.css';
import '../../css/b/br6jib3-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ba9o2nfex"/><path class="br6jib3-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:cc" {...props}></Icon>
