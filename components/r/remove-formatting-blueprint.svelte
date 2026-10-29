<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/aygf7bbmo.css';
import '../../css/d/djt24lr8q.css';
import '../../css/b/bb31khzkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="aygf7bbmo wm-k"/><path class="djt24lr8q wm-k"/><path class="bb31khzkn wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:remove-formatting-blueprint" {...props}></Icon>
