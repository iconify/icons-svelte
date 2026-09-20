<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/k/kutuzrblr.css';
import '../../css/h/hz7_q3dyh.css';
import '../../css/p/pn5m_ac8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kutuzrblr"/><path class="hz7_q3dyh"/><path class="pn5m_ac8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-pull-request-draft-sharp-fill" {...props}></Icon>
