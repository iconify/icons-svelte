<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/b/bwk5rwbue.css';
import '../../css/o/okqtn8bwz.css';
import '../../css/z/zcrd39aiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="bwk5rwbue"/><path class="okqtn8bwz"/><path class="zcrd39aiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:cylinder" {...props}></Icon>
