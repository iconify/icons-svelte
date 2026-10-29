<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rbza6nb1s.css';
import '../../css/e/ezjvqs7tz.css';
import '../../css/z/zbrvpac6b.css';
import '../../css/r/r9gvjrbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rbza6nb1s wm-k"/><path class="ezjvqs7tz wm-a"/><path class="wm-k zbrvpac6b"/><path class="r9gvjrbkq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:rose-bouquet-sketch" {...props}></Icon>
