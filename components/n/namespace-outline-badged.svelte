<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_yhajbgl.css';
import '../../css/y/yjfke8kwc.css';
import '../../css/l/lmf0ecbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="h_yhajbgl"/><path class="yjfke8kwc"/><circle class="lmf0ecbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:namespace-outline-badged" {...props}></Icon>
