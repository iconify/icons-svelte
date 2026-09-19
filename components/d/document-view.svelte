<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lgmhddevn.css';
import '../../css/b/b-_0m7wwh.css';
import '../../css/u/ueg81y61d.css';
import '../../css/v/v0akf7b5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="lgmhddevn"/><path class="b-_0m7wwh"/><path class="ueg81y61d"/><path class="v0akf7b5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-view" {...props}></Icon>
