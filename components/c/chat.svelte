<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr7o5cr9r.css';
import '../../css/x/xv07l8uxa.css';
import '../../css/u/u85qrgbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path clip-rule="evenodd" class="lr7o5cr9r"/><path clip-rule="evenodd" class="xv07l8uxa"/><path class="u85qrgbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-ui:chat" {...props}></Icon>
