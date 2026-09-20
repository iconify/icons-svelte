<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pnlw9tbfh.css';
import '../../css/r/rdg5s2amp.css';
import '../../css/w/wkck6fb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pnlw9tbfh"/><path class="rdg5s2amp"/><path class="wkck6fb3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:file-import" {...props}></Icon>
