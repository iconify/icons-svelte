<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m267nrnme.css';
import '../../css/b/b7kihabsw.css';
import '../../css/m/mjew-dblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m267nrnme wm-shadow"/><path class="b7kihabsw wm-k"/><path class="mjew-dblb wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:more-vertical" {...props}></Icon>
