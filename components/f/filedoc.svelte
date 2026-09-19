<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btx7j3qro.css';
import '../../css/p/pfijng4-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="btx7j3qro"/><path class="pfijng4-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:filedoc" {...props}></Icon>
