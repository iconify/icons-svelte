<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a5fcl1b2z.css';
import '../../css/w/wwt-jfbqh.css';
import '../../css/h/hj5hndk9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a5fcl1b2z"/><path class="wwt-jfbqh"/><path class="hj5hndk9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:dictionary-language-book-flat" {...props}></Icon>
