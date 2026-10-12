<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cx1xifj3g.css';
import '../../css/y/yzu-9rb_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cx1xifj3g"/><path class="yzu-9rb_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-pdf-fill-20" {...props}></Icon>
