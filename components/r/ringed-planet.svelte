<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3lszrbzu.css';
import '../../css/j/j7m3f7b1x.css';
import '../../css/y/yjbv-9bhr.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/o/othqjtbbj.css';
import '../../css/j/j-5u9wban.css';
import '../../css/d/dlws54b1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="u3lszrbzu"/><path class="j7m3f7b1x"/><path class="yjbv-9bhr"/><g class="jn8qy4bru"><path class="othqjtbbj"/><path class="j-5u9wban"/><path class="dlws54b1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:ringed-planet" {...props}></Icon>
