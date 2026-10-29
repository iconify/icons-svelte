<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ok3x2mblu.css';
import '../../css/n/nzkawkbvm.css';
import '../../css/b/b0d7m1b7l.css';
import '../../css/h/hhi9yxy6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ok3x2mblu wm-k"/><path class="nzkawkbvm wm-k"/><path class="b0d7m1b7l wm-k"/><path class="hhi9yxy6w wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:gauge" {...props}></Icon>
