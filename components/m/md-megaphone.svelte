<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg1osvr1r.css';
import '../../css/p/pgf0clsgf.css';
import '../../css/s/s0rj7obem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sg1osvr1r"/><path class="pgf0clsgf"/><path class="s0rj7obem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-megaphone" {...props}></Icon>
