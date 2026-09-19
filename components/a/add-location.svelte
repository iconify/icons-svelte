<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jaaaw1bso.css';
import '../../css/n/nlnn0ibiz.css';
import '../../css/x/xdrfk-b8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jaaaw1bso"/><path class="nlnn0ibiz"/><path class="xdrfk-b8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:add-location" {...props}></Icon>
