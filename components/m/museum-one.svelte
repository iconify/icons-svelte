<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/i/ii0wlebwq.css';
import '../../css/l/lqqlthg3z.css';
import '../../css/h/hx_9wvu-g.css';
import '../../css/v/v6juoxv0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ii0wlebwq"/><path class="lqqlthg3z"/><path class="hx_9wvu-g"/><path class="v6juoxv0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:museum-one" {...props}></Icon>
