<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3jxsg1op.css';
import '../../css/k/kt2gkjn1h.css';
import '../../css/p/pejt3f8ll.css';
import '../../css/d/dem270o5u.css';
import '../../css/k/kv2w_5bmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o3jxsg1op"/><path class="kt2gkjn1h"/><path class="pejt3f8ll"/><path class="dem270o5u"/><path class="kv2w_5bmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:lockandkey" {...props}></Icon>
