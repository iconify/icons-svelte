<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-zsa5bjg.css';
import '../../css/j/j0-b_gamb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c-zsa5bjg"/><path class="j0-b_gamb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:document-attach-sharp" {...props}></Icon>
