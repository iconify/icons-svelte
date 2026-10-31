<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh6chvztw.css';
import '../../css/b/bkqc3vq5j.css';
import '../../css/t/tbiebvz0u.css';
import '../../css/j/jxwqwqlrk.css';
import '../../css/g/ga34h2b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<g display="block"><path class="uh6chvztw"/><path class="bkqc3vq5j"/><path class="tbiebvz0u"/><path class="jxwqwqlrk"/><path class="ga34h2b9k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconito:carrot" {...props}></Icon>
