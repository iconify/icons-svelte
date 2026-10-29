<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r141g95mt.css';
import '../../css/w/wl6kj8h9x.css';
import '../../css/r/r2f7wf--x.css';
import '../../css/c/c4b1g3bsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r141g95mt wm-a"/><path class="wl6kj8h9x wm-k"/><path class="r2f7wf--x wm-k"/><path class="c4b1g3bsn wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:highlighter" {...props}></Icon>
