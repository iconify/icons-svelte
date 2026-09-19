<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3fwb-27e.css';
import '../../css/o/owlnadbcb.css';
import '../../css/k/kbe_yhbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q3fwb-27e"/><rect class="owlnadbcb"/><path class="kbe_yhbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:library" {...props}></Icon>
