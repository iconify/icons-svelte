<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm-dbpb1d.css';
import '../../css/j/j9dlgjb4r.css';
import '../../css/e/e-p76g1mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm-dbpb1d wm-shadow"/><path class="j9dlgjb4r wm-k"/><path class="e-p76g1mi wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-pastel:arrow-down" {...props}></Icon>
