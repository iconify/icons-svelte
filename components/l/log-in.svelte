<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq1dzob7h.css';
import '../../css/r/r811kzb8q.css';
import '../../css/a/a9_x0fs_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq1dzob7h wm-k"/><path class="r811kzb8q wm-a"/><path class="a9_x0fs_r wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:log-in" {...props}></Icon>
