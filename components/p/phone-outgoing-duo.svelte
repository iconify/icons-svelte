<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kluierb0w.css';
import '../../css/z/zo9frohsb.css';
import '../../css/s/spnf93r-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="kluierb0w"/><path class="wm-s zo9frohsb"/><path class="spnf93r-f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:phone-outgoing-duo" {...props}></Icon>
