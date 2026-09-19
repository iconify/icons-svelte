<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hxkoqb07q.css';
import '../../css/g/go4d8z99l.css';
import '../../css/w/weboadcul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="cuyn6tgcc"><path class="hxkoqb07q"/><path class="go4d8z99l"/><path class="weboadcul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:jasmine-wordmark" {...props}></Icon>
