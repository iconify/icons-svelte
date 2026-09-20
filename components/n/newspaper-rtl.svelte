<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtfrwnbwr.css';
import '../../css/z/zhvv4ogqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qtfrwnbwr"/><path class="zhvv4ogqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:newspaper-rtl" {...props}></Icon>
