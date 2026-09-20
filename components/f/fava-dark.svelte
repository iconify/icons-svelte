<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2wxgo90t.css';
import '../../css/b/bo9f9s_he.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w2wxgo90t"/><path class="bo9f9s_he"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fava-dark" {...props}></Icon>
