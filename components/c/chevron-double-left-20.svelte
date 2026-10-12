<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypvhh7b9x.css';
import '../../css/w/w2aqxxbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ypvhh7b9x"/><path class="w2aqxxbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-left-20" {...props}></Icon>
