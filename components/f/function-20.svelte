<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pghs5ubcb.css';
import '../../css/k/kuvw34acp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pghs5ubcb"/><path class="kuvw34acp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:function-20" {...props}></Icon>
