<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmwnk3p6s.css';
import '../../css/u/uar01lb2v.css';
import '../../css/p/p2sew--qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cmwnk3p6s"/><path clip-rule="evenodd" class="uar01lb2v"/><path class="p2sew--qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:commanda-cohere" {...props}></Icon>
