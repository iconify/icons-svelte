<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nyuplcwja.css';
import '../../css/c/cfsulbc1g.css';
import '../../css/j/j_n-5hl9n.css';
import '../../css/w/wd-wa2irw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nyuplcwja"/><path class="cfsulbc1g"/><path class="j_n-5hl9n"/><path class="wd-wa2irw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:microphone" {...props}></Icon>
